<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt65pdnfo.css';
import '../../css/z/zj1ulpbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="yt65pdnfo"/><path class="zj1ulpbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:body-outline" /></template>

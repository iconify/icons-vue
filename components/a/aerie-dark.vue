<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztr6djm4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ztr6djm4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aerie-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe4b7xbxm.css';
import '../../css/n/ncwehzbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fe4b7xbxm"/><path class="ncwehzbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:fish-sharp" /></template>

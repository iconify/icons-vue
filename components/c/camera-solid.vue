<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4sh_ybhk.css';
import '../../css/z/zna4sbwyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u4sh_ybhk"/><path clip-rule="evenodd" class="zna4sbwyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:camera-solid" /></template>

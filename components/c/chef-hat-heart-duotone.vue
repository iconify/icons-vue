<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/prxbgwngf.css';
import '../../css/u/ui-bcv6yx.css';
import '../../css/u/ubnma2bri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="prxbgwngf"/><path class="ui-bcv6yx"/><path class="ubnma2bri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chef-hat-heart-duotone" /></template>

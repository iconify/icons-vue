<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2wg_xbzr.css';
import '../../css/h/huflwkbsf.css';
import '../../css/y/yp4zj8ohv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="x2wg_xbzr"/><path class="huflwkbsf"/><path class="yp4zj8ohv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:lwc" /></template>

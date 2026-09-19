<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xte2y8b6s.css';
import '../../css/y/ygqhxjblw.css';
import '../../css/s/stpu0nbcx.css';
import '../../css/o/ob2lfwuos.css';
import '../../css/z/zu7l1lbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xte2y8b6s"/><path class="ygqhxjblw"/><path class="stpu0nbcx"/><path class="ob2lfwuos"/><path class="zu7l1lbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:googleappscript" /></template>

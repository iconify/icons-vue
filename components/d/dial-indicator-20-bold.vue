<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptmrf5_xm.css';
import '../../css/j/j-b6puwvk.css';
import '../../css/j/jeh1gm_0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ptmrf5_xm"/><path class="j-b6puwvk"/><path class="jeh1gm_0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dial-indicator-20-bold" /></template>

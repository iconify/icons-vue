<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-kgrhb0e.css';
import '../../css/c/clr-_gv_i.css';
import '../../css/p/ptl4ptbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n-kgrhb0e"/><path class="clr-_gv_i"/><path class="ptl4ptbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bug-outline" /></template>

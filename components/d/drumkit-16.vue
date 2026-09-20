<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxp_ne7lq.css';
import '../../css/i/ik8lqcbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mxp_ne7lq"/><path clip-rule="evenodd" class="ik8lqcbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:drumkit-16" /></template>

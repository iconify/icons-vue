<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqa8c8hrf.css';
import '../../css/c/c4121g0qx.css';
import '../../css/n/ntm445bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jqa8c8hrf"/><path class="c4121g0qx"/><path class="ntm445bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:images-20-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ownc4obbs.css';
import '../../css/w/w0z-12ljo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ownc4obbs"/><path class="w0z-12ljo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-diabetes-education" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htn-dr4sx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="htn-dr4sx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:email" /></template>

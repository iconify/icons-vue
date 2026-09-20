<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfot2jebo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kfot2jebo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:control-buttons-skip-forward" /></template>

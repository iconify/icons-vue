<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkbfyf_pr.css';
import '../../css/m/md69zlb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jkbfyf_pr"/><path class="md69zlb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:location" /></template>

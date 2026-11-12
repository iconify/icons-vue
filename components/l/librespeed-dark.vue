<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6yvvac9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l6yvvac9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:librespeed-dark" /></template>

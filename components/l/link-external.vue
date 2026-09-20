<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4ji765zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="x4ji765zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:link-external" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl7-9-bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kl7-9-bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-media-16" /></template>

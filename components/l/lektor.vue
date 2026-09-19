<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0fe3vb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s0fe3vb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:lektor" /></template>

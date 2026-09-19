<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx4_asb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rx4_asb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:jsonnet" /></template>

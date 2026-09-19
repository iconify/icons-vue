<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt1rccc2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":487,"height":512};
const content = `<path class="dt1rccc2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:grapher" /></template>

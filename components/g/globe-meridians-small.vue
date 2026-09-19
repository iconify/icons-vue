<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx5ddjbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rx5ddjbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:globe-meridians-small" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxhop7skf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxhop7skf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:candy" /></template>

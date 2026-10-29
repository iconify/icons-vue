<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgy0btxid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgy0btxid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:arrow-big-up" /></template>

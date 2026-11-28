<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oari8sbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oari8sbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:archive" /></template>

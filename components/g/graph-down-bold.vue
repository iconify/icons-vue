<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o53rsb-vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o53rsb-vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:graph-down-bold" /></template>

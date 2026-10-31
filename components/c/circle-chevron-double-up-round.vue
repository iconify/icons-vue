<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdbc1eb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdbc1eb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-chevron-double-up-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubv0g8btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubv0g8btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-empty-fill-round" /></template>

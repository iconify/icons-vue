<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z68460bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z68460bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:charging-station" /></template>

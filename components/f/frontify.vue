<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dog50kb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dog50kb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:frontify" /></template>

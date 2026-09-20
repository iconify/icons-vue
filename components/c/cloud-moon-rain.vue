<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2ltmhbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2ltmhbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:cloud-moon-rain" /></template>

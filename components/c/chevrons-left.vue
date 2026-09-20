<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clpy71bca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clpy71bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:chevrons-left" /></template>

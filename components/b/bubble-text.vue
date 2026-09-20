<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nixyq4bzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nixyq4bzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bubble-text" /></template>

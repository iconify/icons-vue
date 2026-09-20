<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is2b7bcwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="is2b7bcwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:droplet-question" /></template>

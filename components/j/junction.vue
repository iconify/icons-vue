<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ih0p_rboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ih0p_rboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:junction" /></template>

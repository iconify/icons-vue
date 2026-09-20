<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s10ohtb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s10ohtb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:coronavirus" /></template>

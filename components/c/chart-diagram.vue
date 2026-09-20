<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxfnjdc7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxfnjdc7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-diagram" /></template>

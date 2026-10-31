<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9afo1r9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9afo1r9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-right-fill-round" /></template>

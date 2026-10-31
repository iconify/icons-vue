<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-0k6ir6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-0k6ir6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fuel-fill-round" /></template>

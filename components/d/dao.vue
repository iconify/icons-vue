<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dybil4b0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dybil4b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dao" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4g1499jw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4g1499jw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-12-round" /></template>

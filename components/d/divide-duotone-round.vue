<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trvs4ey0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trvs4ey0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:divide-duotone-round" /></template>

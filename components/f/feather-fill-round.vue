<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu791xb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu791xb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:feather-fill-round" /></template>

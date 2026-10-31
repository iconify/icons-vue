<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l273n2buk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l273n2buk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-2-round" /></template>

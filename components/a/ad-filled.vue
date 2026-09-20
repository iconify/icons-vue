<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu75auegt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu75auegt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ad-filled" /></template>

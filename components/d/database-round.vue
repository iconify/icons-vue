<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dipl2zbia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dipl2zbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:database-round" /></template>

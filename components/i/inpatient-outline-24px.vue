<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja_877gin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ja_877gin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:inpatient-outline-24px" /></template>

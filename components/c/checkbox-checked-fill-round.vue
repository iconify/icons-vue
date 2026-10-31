<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq7f3kb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq7f3kb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:checkbox-checked-fill-round" /></template>

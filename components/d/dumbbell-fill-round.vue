<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqpdxihwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqpdxihwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dumbbell-fill-round" /></template>

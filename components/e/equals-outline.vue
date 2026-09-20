<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4-_r6b9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4-_r6b9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:equals-outline" /></template>

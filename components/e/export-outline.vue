<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0whs1-mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0whs1-mv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:export-outline" /></template>

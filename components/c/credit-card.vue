<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrhb9mvxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrhb9mvxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:credit-card" /></template>

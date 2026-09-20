<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3yi4ibis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3yi4ibis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:credit-card-edit-outline" /></template>

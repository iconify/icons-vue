<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aldc2_b0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aldc2_b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:credit-card-remove-outline" /></template>

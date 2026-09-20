<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlkqo4fwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xlkqo4fwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:expressionless-square-bold" /></template>

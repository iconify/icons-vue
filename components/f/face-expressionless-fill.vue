<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa0d8lorg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa0d8lorg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-expressionless-fill" /></template>

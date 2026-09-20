<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2sa2gbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m2sa2gbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alarm-add-outline" /></template>

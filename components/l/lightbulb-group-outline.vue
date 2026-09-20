<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t44l9wbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t44l9wbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lightbulb-group-outline" /></template>

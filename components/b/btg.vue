<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nicvw8b7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nicvw8b7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:btg" /></template>

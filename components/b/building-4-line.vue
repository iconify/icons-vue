<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5o7mcc7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5o7mcc7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:building-4-line" /></template>

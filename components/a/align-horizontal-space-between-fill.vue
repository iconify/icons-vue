<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6a3wwbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6a3wwbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:align-horizontal-space-between-fill" /></template>

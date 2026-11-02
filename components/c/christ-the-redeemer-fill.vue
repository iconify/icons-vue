<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q591nmoit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q591nmoit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:christ-the-redeemer-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5m5mqbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5m5mqbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:desk-stand" /></template>

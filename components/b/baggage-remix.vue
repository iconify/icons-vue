<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp9_yjb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zp9_yjb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:baggage-remix" /></template>

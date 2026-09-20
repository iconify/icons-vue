<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj59mebze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zj59mebze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:credit-card-2-remix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzv55vozr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wzv55vozr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-up-4-square-fill" /></template>

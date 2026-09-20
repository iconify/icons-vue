<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h389tou-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h389tou-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-phone-alt-1-line" /></template>

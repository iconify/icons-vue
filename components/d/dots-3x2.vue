<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foiny1xyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="foiny1xyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-3x2" /></template>

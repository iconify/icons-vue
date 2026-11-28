<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldwjd48ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldwjd48ex primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevrons-left-right-duotone" /></template>

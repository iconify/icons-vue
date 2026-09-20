<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqwpg6beq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqwpg6beq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:badge-alert" /></template>

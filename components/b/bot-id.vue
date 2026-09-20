<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d07qm6b6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d07qm6b6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bot-id" /></template>

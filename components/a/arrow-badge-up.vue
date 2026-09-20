<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s26z6pb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s26z6pb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-badge-up" /></template>

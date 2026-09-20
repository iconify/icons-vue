<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4fw1mb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4fw1mb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:exchange-funds-line" /></template>

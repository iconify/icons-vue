<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfipemz8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfipemz8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:headphones-box" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3qb3wiwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3qb3wiwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dice-2-line" /></template>

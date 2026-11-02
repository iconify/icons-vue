<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo585-bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lo585-bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:diary-line" /></template>

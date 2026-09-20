<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/toh8bgboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="toh8bgboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:credit-card-fill" /></template>

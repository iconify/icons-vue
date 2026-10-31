<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noom4acdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="noom4acdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:compass-solid" /></template>

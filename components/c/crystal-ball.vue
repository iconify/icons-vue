<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo8je1bqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fo8je1bqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:crystal-ball" /></template>

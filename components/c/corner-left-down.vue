<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzc8v-b8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzc8v-b8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:corner-left-down" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5vw760we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5vw760we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bookmark-down" /></template>

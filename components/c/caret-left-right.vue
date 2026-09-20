<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y37et8bgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y37et8bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:caret-left-right" /></template>

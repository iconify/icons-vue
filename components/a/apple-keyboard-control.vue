<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd3xg04we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd3xg04we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:apple-keyboard-control" /></template>

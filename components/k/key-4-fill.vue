<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc52ak1ch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc52ak1ch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:key-4-fill" /></template>

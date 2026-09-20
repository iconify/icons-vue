<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owj4jnl7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owj4jnl7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:horse-variant-fast" /></template>

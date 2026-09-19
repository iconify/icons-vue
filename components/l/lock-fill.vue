<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djo_9gben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="djo_9gben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:lock-fill" /></template>

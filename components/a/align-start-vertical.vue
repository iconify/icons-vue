<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa5486b-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa5486b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:align-start-vertical" /></template>

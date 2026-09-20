<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gedfccb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gedfccb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:cellular-network-5g-remix" /></template>

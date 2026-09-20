<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owioo-z8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owioo-z8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:filter-1" /></template>

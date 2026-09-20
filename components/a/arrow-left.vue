<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip8wo8bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip8wo8bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:arrow-left" /></template>

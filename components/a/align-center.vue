<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6l3qbczg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6l3qbczg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:align-center" /></template>

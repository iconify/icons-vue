<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8lynkn4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8lynkn4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:arrow-to-top" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok96sibyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ok96sibyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:filter-2-minus" /></template>

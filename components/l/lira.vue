<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/en241i7xq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en241i7xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:lira" /></template>

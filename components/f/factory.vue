<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq3j0ibkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq3j0ibkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:factory" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn0rtdylg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn0rtdylg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:border-none-01" /></template>

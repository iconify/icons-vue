<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk7w1m6ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk7w1m6ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:drinks-2-fill" /></template>

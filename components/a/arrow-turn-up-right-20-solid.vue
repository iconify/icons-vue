<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wstprc37e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wstprc37e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-up-right-20-solid" /></template>

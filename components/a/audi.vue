<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guqzcut-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guqzcut-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:audi" /></template>

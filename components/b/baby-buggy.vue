<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uduv0nq8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uduv0nq8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:baby-buggy" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jor686bkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jor686bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:kettlebell" /></template>

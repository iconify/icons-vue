<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b85g23sbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b85g23sbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alert-plus-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6182_c6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6182_c6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-t-circle" /></template>

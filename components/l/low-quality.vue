<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s906swbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s906swbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:low-quality" /></template>

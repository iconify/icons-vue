<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owf8r9b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owf8r9b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cash-100" /></template>

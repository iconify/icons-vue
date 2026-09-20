<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwlc1fzvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwlc1fzvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flag-bitcoin" /></template>

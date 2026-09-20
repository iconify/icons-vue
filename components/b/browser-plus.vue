<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5iq_5iok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5iq_5iok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:browser-plus" /></template>

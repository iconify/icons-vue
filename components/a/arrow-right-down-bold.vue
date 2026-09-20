<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzmi8obmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzmi8obmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-right-down-bold" /></template>

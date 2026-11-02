<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnznm6t1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnznm6t1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mail-check-fill" /></template>

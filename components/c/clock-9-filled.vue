<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e693plb3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e693plb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:clock-9-filled" /></template>

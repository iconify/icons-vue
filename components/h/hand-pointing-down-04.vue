<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbx7ydbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbx7ydbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hand-pointing-down-04" /></template>

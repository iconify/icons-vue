<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyzcrx07p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyzcrx07p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:indent-decrease-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm3hlnbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm3hlnbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:imac-fill" /></template>

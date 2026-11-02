<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9dsm16-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9dsm16-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clipboard-x-fill" /></template>

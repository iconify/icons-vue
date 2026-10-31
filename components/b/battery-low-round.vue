<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etel5odht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etel5odht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-low-round" /></template>

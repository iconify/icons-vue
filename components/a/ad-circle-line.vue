<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sim8i5tck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sim8i5tck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ad-circle-line" /></template>

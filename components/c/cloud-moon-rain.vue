<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3j5e8bel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3j5e8bel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cloud-moon-rain" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqz1gepph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqz1gepph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:arrow-big-up-dash-filled" /></template>

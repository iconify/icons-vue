<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhau-5bid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhau-5bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cast-line" /></template>

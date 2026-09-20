<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4vixbb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4vixbb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:direction-arrow-fill" /></template>

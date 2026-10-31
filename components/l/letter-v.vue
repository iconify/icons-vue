<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvhz7hd7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvhz7hd7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:letter-v" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu7x7cbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu7x7cbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brackets-angle-line" /></template>

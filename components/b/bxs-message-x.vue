<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk2k54bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk2k54bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-message-x" /></template>

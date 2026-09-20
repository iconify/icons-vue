<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijcd3cbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijcd3cbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:epson" /></template>

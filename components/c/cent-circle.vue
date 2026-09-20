<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkay--b3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mkay--b3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:cent-circle" /></template>

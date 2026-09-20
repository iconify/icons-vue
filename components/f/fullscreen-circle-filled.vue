<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcdehjbth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kcdehjbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:fullscreen-circle-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu23s0b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eu23s0b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:foundryvirtualtabletop" /></template>

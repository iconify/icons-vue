<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo0h7bcsg.css';
import '../../css/r/rh51rxbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vo0h7bcsg"/><path class="rh51rxbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:iron-48-bold" /></template>

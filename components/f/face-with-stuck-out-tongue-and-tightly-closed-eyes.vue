<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyscs09jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="wyscs09jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:face-with-stuck-out-tongue-and-tightly-closed-eyes" /></template>

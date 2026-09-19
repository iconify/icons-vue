<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7bwtwbet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y7bwtwbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:adobe-audition" /></template>

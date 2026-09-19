<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kci5s6b3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":441,"height":512};
const content = `<path class="kci5s6b3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:dragonflybsd" /></template>

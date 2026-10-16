<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lam0-jatz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lam0-jatz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevrons-up-down-20-bold" /></template>

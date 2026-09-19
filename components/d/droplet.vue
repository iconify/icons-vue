<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx4405b0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kx4405b0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:droplet" /></template>

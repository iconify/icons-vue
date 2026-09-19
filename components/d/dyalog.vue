<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-os__b8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":416,"height":512};
const content = `<path class="s-os__b8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:dyalog" /></template>

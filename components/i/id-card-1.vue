<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyewzpp7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tyewzpp7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:id-card-1" /></template>

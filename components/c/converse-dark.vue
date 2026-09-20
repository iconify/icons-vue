<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n95rl0b7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n95rl0b7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:converse-dark" /></template>

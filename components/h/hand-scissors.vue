<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srjvx7b4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="srjvx7b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hand-scissors" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glhgli7le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="glhgli7le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:amputation" /></template>

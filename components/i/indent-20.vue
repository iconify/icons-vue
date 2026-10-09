<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1tcy5bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c1tcy5bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:indent-20" /></template>

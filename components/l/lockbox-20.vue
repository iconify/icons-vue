<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axles5bjl.css';
import '../../css/g/guuynvblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="axles5bjl"/><path class="guuynvblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lockbox-20" /></template>

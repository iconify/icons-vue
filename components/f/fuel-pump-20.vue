<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iixfqsbra.css';
import '../../css/u/upuxwyb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iixfqsbra"/><path class="upuxwyb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fuel-pump-20" /></template>

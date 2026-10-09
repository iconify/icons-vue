<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9obxowyy.css';
import '../../css/n/n1rnmdo-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i9obxowyy"/><path class="n1rnmdo-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:award-20" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcqo0cvhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcqo0cvhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:caravan" /></template>

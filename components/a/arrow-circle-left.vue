<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guhhauoca.css';
import '../../css/p/py4wsctwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guhhauoca"/><path class="py4wsctwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:arrow-circle-left" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh11dfbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kh11dfbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:alarm-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saail3bjj.css';
import '../../css/v/v58dvfb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="saail3bjj"/><path class="v58dvfb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:level-gauge-20-bold" /></template>

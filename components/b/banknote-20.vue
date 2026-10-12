<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoams9w2x.css';
import '../../css/t/tnqh3bc1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uoams9w2x"/><path class="tnqh3bc1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:banknote-20" /></template>

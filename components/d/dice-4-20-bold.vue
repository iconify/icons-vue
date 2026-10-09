<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfgcicctr.css';
import '../../css/d/dwmd5bb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sfgcicctr"/><path class="dwmd5bb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dice-4-20-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g--bxo5in.css';
import '../../css/x/xxzut0e2z.css';
import '../../css/q/qh3-d7bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g--bxo5in"/><path class="xxzut0e2z"/><path class="qh3-d7bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lock-check-20" /></template>

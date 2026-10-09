<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2x88vmhw.css';
import '../../css/p/pv9k0lrqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i2x88vmhw"/><path class="pv9k0lrqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dam-20-bold" /></template>

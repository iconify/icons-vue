<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv8y42b4f.css';
import '../../css/j/j79qmbgbf.css';
import '../../css/f/f2nkggpoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pv8y42b4f"/><path class="j79qmbgbf"/><path class="f2nkggpoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:luggage-20" /></template>

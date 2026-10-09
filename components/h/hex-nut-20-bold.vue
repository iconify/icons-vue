<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7nqvkavv.css';
import '../../css/b/bu587_boe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s7nqvkavv"/><path class="bu587_boe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hex-nut-20-bold" /></template>

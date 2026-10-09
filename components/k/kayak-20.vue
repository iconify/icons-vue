<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx6i4llwi.css';
import '../../css/w/woo7zdu1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mx6i4llwi"/><path class="woo7zdu1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kayak-20" /></template>

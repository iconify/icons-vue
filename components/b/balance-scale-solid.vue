<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-3desbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g-3desbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:balance-scale-solid" /></template>

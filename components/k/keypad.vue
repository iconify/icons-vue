<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku3mnebwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ku3mnebwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:keypad" /></template>

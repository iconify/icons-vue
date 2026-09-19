<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc90pxb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sc90pxb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:bluetoothconnected" /></template>

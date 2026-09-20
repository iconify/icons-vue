<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qib8-s6ft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qib8-s6ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bagel" /></template>

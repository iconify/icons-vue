<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cckjnebfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":456,"height":384};
const content = `<path class="cckjnebfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:airline-seat-flat-angled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uslkuubfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uslkuubfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:ceiling-lamp" /></template>

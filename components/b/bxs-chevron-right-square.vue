<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksbqztbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksbqztbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-chevron-right-square" /></template>

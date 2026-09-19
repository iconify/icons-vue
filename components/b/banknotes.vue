<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0kinc8xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0kinc8xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:banknotes" /></template>

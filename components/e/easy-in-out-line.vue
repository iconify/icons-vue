<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_e2u0buw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_e2u0buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:easy-in-out-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t26_t2uqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t26_t2uqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lamp-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_8c5nbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_8c5nbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-envelope" /></template>

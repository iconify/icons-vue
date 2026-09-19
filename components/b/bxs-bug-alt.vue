<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/masogxblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="masogxblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-bug-alt" /></template>

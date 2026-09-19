<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sonqz8bzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sonqz8bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-user" /></template>

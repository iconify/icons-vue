<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo-ryxbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="jo-ryxbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:hammer-2" /></template>

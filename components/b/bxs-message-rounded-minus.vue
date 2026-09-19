<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhw0htbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhw0htbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-message-rounded-minus" /></template>

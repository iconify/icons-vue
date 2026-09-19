<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld10qmhob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld10qmhob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cart-alt-filled" /></template>

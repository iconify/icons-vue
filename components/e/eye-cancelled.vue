<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehqakfbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ehqakfbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:eye-cancelled" /></template>

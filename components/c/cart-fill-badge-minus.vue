<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q841-ov0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="q841-ov0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:cart-fill-badge-minus" /></template>

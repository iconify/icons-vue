<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfm31cbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="dfm31cbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:cart-badge-minus" /></template>

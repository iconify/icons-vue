<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw_au-gcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="zw_au-gcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-nine-small" /></template>

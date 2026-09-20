<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkxnt0j7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qkxnt0j7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:add-eye" /></template>

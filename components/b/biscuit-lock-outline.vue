<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znt4_dbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znt4_dbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:biscuit-lock-outline" /></template>

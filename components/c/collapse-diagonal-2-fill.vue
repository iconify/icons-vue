<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9skfif3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9skfif3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:collapse-diagonal-2-fill" /></template>

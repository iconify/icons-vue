<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcj4w92ez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcj4w92ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alt-arrow-left-broken" /></template>

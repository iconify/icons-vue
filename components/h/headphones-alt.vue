<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttosrdn2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttosrdn2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:headphones-alt" /></template>

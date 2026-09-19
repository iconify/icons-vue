<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqrrc0bch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqrrc0bch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:box-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k963vjbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k963vjbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cone-fill" /></template>

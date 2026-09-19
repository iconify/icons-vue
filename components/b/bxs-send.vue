<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_58qlbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_58qlbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-send" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij78l-lsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij78l-lsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cash-banknote-filled" /></template>

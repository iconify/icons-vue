<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu1lb4brs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nu1lb4brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-guarani" /></template>

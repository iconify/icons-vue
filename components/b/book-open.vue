<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch4_lnb0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch4_lnb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:book-open" /></template>

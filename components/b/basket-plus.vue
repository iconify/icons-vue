<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr5o16b_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr5o16b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:basket-plus" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd71a5b1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pd71a5b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cart-minus" /></template>

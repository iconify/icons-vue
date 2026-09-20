<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t12f6_cmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t12f6_cmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:cart-add" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mar89_b7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mar89_b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-to-left-stroke" /></template>

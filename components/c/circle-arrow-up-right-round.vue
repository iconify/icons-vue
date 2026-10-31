<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1i4gnl2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1i4gnl2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-arrow-up-right-round" /></template>

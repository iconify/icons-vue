<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0n1cjchm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0n1cjchm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:discount-filled" /></template>

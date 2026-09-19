<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlgy8mm_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlgy8mm_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:alarm-check-filled" /></template>

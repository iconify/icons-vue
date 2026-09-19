<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doqq05v5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="doqq05v5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:icecream-filled" /></template>

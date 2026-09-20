<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idgt6wb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idgt6wb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:feather" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lais3ymnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lais3ymnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:dribbble" /></template>

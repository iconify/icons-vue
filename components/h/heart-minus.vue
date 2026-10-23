<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlqvonbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlqvonbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:heart-minus" /></template>

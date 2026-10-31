<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sih6heblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sih6heblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:car-side-fill-round" /></template>

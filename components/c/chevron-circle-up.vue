<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxvahv4on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="kxvahv4on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevron-circle-up" /></template>

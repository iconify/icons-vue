<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cje30fbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cje30fbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:anchor-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjpzwqpcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjpzwqpcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:chevron-double-up" /></template>

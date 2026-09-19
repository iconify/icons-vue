<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uinxx6akt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uinxx6akt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:book-close" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk_xkpb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rk_xkpb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:contact-book-solid" /></template>

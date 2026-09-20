<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_-uxf2in.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_-uxf2in"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:currency-sign-franc" /></template>

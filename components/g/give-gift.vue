<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd876c3xz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd876c3xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:give-gift" /></template>

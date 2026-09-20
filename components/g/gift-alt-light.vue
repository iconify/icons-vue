<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq3i879dg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="mq3i879dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:gift-alt-light" /></template>

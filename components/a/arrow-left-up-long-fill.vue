<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st1qoibzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st1qoibzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-up-long-fill" /></template>

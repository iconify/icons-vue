<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i162iyc8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i162iyc8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:eye-off-fill" /></template>

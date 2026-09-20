<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aesn7b_0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aesn7b_0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:data-plus-line" /></template>

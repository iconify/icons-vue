<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp8cm7rty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp8cm7rty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:git-pull-request-create-arrow" /></template>

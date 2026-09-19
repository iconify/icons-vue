<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-9f0eb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-9f0eb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:book-open-text" /></template>

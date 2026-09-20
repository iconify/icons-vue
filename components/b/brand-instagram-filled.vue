<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbsus4b4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbsus4b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-instagram-filled" /></template>

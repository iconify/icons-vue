<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl6d73b_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tl6d73b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:colour-tuneing-bold" /></template>

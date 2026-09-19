<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8ict-bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8ict-bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:computer" /></template>

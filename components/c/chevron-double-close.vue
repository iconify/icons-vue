<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veyi8bc9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="veyi8bc9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:chevron-double-close" /></template>

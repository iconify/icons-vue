<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cj978js3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cj978js3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-spray-can" /></template>

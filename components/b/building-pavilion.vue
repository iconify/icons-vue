<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4e1w5h4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4e1w5h4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-pavilion" /></template>

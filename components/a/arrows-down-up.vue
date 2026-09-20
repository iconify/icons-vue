<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8p8ekymi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8p8ekymi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrows-down-up" /></template>

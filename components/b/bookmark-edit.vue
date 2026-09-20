<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eht1iybet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eht1iybet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bookmark-edit" /></template>

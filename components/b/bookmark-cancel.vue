<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwyjs1bma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwyjs1bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bookmark-cancel" /></template>

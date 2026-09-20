<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve_3q8ezo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve_3q8ezo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bookmark-filled" /></template>

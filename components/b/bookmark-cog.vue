<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4w-kt03b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4w-kt03b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bookmark-cog" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abn7u8b5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abn7u8b5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-line-decreasing-sharp" /></template>

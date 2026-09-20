<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5e9y-bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5e9y-bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:landing" /></template>

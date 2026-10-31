<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu9u27bcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nu9u27bcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cow-round" /></template>

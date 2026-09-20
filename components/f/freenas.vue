<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9k372bem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9k372bem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:freenas" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlvcwvbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlvcwvbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:caret-left-outline" /></template>

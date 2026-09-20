<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmhvwsexb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmhvwsexb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bookmark-sharp" /></template>

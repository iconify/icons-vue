<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxxo6lb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dxxo6lb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:magnifying-glass-remix" /></template>

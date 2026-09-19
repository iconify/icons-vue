<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haqpj0bif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="haqpj0bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:gitpod" /></template>

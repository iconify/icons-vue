<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/toh_b0f4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="toh_b0f4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:banknote-fill" /></template>

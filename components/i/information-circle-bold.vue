<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyg7nob9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyg7nob9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:information-circle-bold" /></template>

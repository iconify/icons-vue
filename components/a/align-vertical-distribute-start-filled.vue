<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0m6_7bfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0m6_7bfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:align-vertical-distribute-start-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rln4a3--c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rln4a3--c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:broom-filled" /></template>

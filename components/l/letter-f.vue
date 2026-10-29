<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azoqlsbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azoqlsbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:letter-f" /></template>

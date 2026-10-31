<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2ssfjwif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2ssfjwif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-open-fill-round" /></template>

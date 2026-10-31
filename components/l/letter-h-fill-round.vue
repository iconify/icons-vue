<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-d78hkpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-d78hkpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-h-fill-round" /></template>

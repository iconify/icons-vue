<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bibsbeu0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bibsbeu0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coffee-to-go-round" /></template>

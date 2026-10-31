<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqvyfqbgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqvyfqbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fox-round" /></template>

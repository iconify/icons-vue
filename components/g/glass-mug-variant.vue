<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6fugovua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6fugovua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:glass-mug-variant" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soy-c7b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="soy-c7b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:h6" /></template>

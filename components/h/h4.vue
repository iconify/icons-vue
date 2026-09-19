<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xviqmb0wz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xviqmb0wz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:h4" /></template>

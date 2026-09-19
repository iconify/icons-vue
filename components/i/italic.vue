<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp6qv9b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp6qv9b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:italic" /></template>

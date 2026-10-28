<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu9somb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu9somb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:border" /></template>

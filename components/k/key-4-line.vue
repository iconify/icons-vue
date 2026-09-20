<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgz7o1bwh.css';
import '../../css/a/atikj6bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgz7o1bwh"/><circle class="atikj6bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:key-4-line" /></template>

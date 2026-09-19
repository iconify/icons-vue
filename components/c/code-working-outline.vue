<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuejpjjmz.css';
import '../../css/b/be4ff7bzh.css';
import '../../css/z/zhu4enjix.css';
import '../../css/u/u2bhkjb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="vuejpjjmz"/><circle class="be4ff7bzh"/><circle class="zhu4enjix"/><path class="u2bhkjb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:code-working-outline" /></template>

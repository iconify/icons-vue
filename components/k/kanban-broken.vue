<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/b4f6f8byj.css';
import '../../css/q/qren0kb9n.css';
import '../../css/w/whspc0b_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b4f6f8byj"/><path class="qren0kb9n"/><path class="whspc0b_i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:kanban-broken" /></template>

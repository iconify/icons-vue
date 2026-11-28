<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6qud1_5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6qud1_5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cart-refresh" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic8udy9nn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ic8udy9nn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:lightbulb-stroke-20" /></template>

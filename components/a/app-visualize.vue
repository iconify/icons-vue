<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7js7wb7z.css';
import '../../css/h/hvxpjjbnu.css';
import '../../css/y/y2-y6r8-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j7js7wb7z ouiIcon__fillSecondary"/><path class="hvxpjjbnu"/><path class="y2-y6r8-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-visualize" /></template>

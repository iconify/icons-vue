<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agla4pb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agla4pb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:italic" /></template>

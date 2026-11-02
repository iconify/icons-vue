<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voibx9b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="voibx9b5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lie-down-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lefpkgb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lefpkgb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:liver-outline-24px" /></template>

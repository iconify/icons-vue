<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5ffo1bso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5ffo1bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:border-horizontal" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cme5uzbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cme5uzbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-search-lines" /></template>

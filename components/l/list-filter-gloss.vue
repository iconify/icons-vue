<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-_crhbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-_crhbid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-filter-gloss" /></template>

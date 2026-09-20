<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oupyt1nha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oupyt1nha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:corner-down-right" /></template>

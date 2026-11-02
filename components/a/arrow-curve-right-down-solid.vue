<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r86t9sbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r86t9sbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-curve-right-down-solid" /></template>

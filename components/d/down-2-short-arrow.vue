<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb-n7kb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb-n7kb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:down-2-short-arrow" /></template>

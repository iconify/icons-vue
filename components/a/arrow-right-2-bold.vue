<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqv85o6cb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqv85o6cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-right-2-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6eo6ewzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6eo6ewzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fold-horizontal-line" /></template>

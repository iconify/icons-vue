<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd9l58i1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd9l58i1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bar-code-01" /></template>

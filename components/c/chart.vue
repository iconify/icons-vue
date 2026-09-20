<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1parx3gv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q1parx3gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:chart" /></template>

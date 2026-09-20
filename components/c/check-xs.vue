<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl8fc0bgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="cl8fc0bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:check-xs" /></template>

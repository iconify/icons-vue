<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi-bafbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gi-bafbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:left-indent-alt" /></template>

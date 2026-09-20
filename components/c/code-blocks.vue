<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ziaa1cqwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ziaa1cqwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:code-blocks" /></template>

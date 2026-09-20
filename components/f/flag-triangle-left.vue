<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7y1ieb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7y1ieb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:flag-triangle-left" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2d9zgb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2d9zgb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:anchor-fill" /></template>

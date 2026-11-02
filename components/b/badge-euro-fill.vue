<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clg8mbq-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clg8mbq-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:badge-euro-fill" /></template>

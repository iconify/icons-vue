<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3yoi7b1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3yoi7b1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:glass-cup-line" /></template>

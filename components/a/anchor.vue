<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s41z9kb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s41z9kb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:anchor" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_87rhb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="t_87rhb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hash-outline" /></template>

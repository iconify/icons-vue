<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s68c4_3ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="s68c4_3ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:drop-triangle-fill" /></template>

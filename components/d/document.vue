<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkhq120ey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jkhq120ey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:document" /></template>

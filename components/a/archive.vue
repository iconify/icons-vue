<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f79jhmb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="f79jhmb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:archive" /></template>

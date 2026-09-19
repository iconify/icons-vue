<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrhi1zbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="rrhi1zbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:idea-alt" /></template>

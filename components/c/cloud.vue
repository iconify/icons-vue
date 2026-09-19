<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jru89b19c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="jru89b19c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:cloud" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hehtalizt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="hehtalizt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:chevron-up" /></template>

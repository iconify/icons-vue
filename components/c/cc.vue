<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thmpixb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="thmpixb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:cc" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqg2w0bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="mqg2w0bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:child" /></template>

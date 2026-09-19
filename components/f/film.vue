<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np3_u8p3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="np3_u8p3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:film" /></template>

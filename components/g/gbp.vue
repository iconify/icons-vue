<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg_-8gbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="jg_-8gbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:gbp" /></template>

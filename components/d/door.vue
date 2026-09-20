<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7yuo4hsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="g7yuo4hsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:door" /></template>

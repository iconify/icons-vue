<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9orm0blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="j9orm0blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:hourglass0" /></template>

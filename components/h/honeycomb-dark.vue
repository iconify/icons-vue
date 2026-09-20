<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrnfgtxba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":164,"height":48};
const content = `<path class="zrnfgtxba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:honeycomb-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc-dtnblr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="oc-dtnblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:clipboard-list" /></template>

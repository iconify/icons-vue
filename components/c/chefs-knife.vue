<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhneexb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qhneexb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:chefs-knife" /></template>

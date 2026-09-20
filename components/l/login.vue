<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apmn47bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="apmn47bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:login" /></template>

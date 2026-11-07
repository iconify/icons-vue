<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqm6qeb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yqm6qeb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dog-wearing-collar-in-eaved-leanto-building" /></template>

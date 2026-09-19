<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhhvm1c5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="vhhvm1c5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:cloud" /></template>

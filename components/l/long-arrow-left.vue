<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bys7cd0-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="bys7cd0-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:long-arrow-left" /></template>

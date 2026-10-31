<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yawaon_6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yawaon_6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eaved-open-gabled-building-with-door" /></template>

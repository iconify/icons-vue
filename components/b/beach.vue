<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfi9zl2px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gfi9zl2px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:beach" /></template>

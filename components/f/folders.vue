<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq3z2ybyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gq3z2ybyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:folders" /></template>

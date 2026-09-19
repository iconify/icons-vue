<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz17u31mk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="tz17u31mk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:googleplus" /></template>

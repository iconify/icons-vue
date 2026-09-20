<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzwc3wbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dzwc3wbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:couch" /></template>

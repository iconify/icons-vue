<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvr_ly5gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hvr_ly5gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:elbow-connector-solid" /></template>

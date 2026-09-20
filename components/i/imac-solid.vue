<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkn7fcxyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wkn7fcxyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:imac-solid" /></template>

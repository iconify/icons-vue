<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5_8t67kc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="q5_8t67kc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:intersection" /></template>

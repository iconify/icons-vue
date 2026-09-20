<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb55csbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yb55csbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:adjust-vertical-outline" /></template>

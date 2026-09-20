<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7ug-0ytb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q7ug-0ytb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lantern" /></template>

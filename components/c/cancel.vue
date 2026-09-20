<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5b2kyb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r5b2kyb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:cancel" /></template>

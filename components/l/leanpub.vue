<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/daysn06po.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="daysn06po"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:leanpub" /></template>

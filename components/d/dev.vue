<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj9mviyqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="xj9mviyqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:dev" /></template>

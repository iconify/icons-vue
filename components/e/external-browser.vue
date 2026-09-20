<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk75-jb2c.css';
import '../../css/b/boxkj20aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dk75-jb2c"/><path class="boxkj20aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:external-browser" /></template>

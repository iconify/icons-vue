<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9a81jbes.css';
import '../../css/e/efn4s4b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r9a81jbes"/><circle class="efn4s4b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-figma" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra5ogubua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ra5ogubua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:bold-cyrl-te" /></template>

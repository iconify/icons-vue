<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r11vufb2b.css';
import '../../css/w/wzrtz78mz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r11vufb2b"/><path class="wzrtz78mz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:banknote-20-bold" /></template>

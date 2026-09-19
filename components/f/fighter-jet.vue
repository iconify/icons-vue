<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkvj90bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1280};
const content = `<path class="jkvj90bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:fighter-jet" /></template>

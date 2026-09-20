<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta7e7h-iw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="ta7e7h-iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:lightbulb" /></template>

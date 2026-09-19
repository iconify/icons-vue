<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a592yis3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="a592yis3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:golf" /></template>

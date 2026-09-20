<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg6azkrhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jg6azkrhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:id-card" /></template>

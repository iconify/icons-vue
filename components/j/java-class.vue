<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o46y79b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o46y79b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:java-class" /></template>

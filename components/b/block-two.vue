<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adjf9fbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="adjf9fbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:block-two" /></template>

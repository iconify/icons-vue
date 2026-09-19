<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l600tsbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l600tsbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clipboard-blank-fill-16" /></template>

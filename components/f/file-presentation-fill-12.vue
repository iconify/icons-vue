<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi6ws9b5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zi6ws9b5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-presentation-fill-12" /></template>

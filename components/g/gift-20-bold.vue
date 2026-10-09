<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r56981bwx.css';
import '../../css/o/ol6cddb-q.css';
import '../../css/y/y954mibjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r56981bwx"/><path class="ol6cddb-q"/><path class="y954mibjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gift-20-bold" /></template>

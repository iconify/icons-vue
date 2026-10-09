<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpf2n7b-t.css';
import '../../css/v/vltu6acye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jpf2n7b-t"/><path class="vltu6acye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:jar-20" /></template>

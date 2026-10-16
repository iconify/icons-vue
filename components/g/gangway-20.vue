<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7wahub6s.css';
import '../../css/j/j0ltuoz_j.css';
import '../../css/s/sd-l4j7ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w7wahub6s"/><path class="j0ltuoz_j"/><path class="sd-l4j7ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gangway-20" /></template>

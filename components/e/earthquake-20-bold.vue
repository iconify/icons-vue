<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gclpr8i1a.css';
import '../../css/r/royu2xbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gclpr8i1a"/><path class="royu2xbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:earthquake-20-bold" /></template>

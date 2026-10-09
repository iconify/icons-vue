<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubixxqbpx.css';
import '../../css/r/rum39npnf.css';
import '../../css/c/cfji69bfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ubixxqbpx"/><path class="rum39npnf"/><path class="cfji69bfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hammock-20" /></template>

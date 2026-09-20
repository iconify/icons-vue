<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ganpgob_x.css';
import '../../css/n/nh_1xf49f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":722.8,"height":702};
const content = `<path class="ganpgob_x"/><path class="nh_1xf49f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kubernetes" /></template>

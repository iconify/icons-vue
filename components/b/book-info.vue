<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j5unwvgdz.css';
import '../../css/n/nx5e8zbhq.css';
import '../../css/g/g33moobtw.css';
import '../../css/f/f59k7yeig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j5unwvgdz"/><path class="nx5e8zbhq"/><path class="g33moobtw"/><circle class="f59k7yeig"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:book-info" /></template>

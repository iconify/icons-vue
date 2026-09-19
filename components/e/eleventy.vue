<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu1wy4b6g.css';
import '../../css/y/yuoo8p78p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="tu1wy4b6g"/><path class="yuoo8p78p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:eleventy" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol2yed01a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ol2yed01a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:gatling-wordmark" /></template>

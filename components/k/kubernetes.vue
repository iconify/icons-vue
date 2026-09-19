<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfxjh-beo.css';
import '../../css/j/j94shoiso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="yfxjh-beo"/><path class="j94shoiso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:kubernetes" /></template>

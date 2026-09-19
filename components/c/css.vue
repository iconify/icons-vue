<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c65pc6_cx.css';
import '../../css/o/ohg47blkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="c65pc6_cx"/><path class="ohg47blkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:css" /></template>

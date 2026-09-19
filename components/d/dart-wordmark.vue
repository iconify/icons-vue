<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxgz0fldn.css';
import '../../css/c/cq5b2q68g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pxgz0fldn"/><path class="cq5b2q68g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:dart-wordmark" /></template>

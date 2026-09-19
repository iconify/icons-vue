<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txt8bqbzk.css';
import '../../css/d/dbsyz0f1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="txt8bqbzk"/><path class="dbsyz0f1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ghost-wordmark" /></template>

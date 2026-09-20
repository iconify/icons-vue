<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/daolku9bq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="daolku9bq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:game-controller" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jih5fdbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="jih5fdbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:archive" /></template>

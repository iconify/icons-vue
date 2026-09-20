<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cye1qenss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="cye1qenss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:format-align-right" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh5r6jayr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="jh5r6jayr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:bus-alt" /></template>

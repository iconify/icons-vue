<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b19q2ulep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b19q2ulep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-big-down-20" /></template>

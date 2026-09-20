<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4j-kd0fo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c4j-kd0fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:game-controller-outline" /></template>

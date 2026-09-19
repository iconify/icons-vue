<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8dp7db7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="r8dp7db7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:diagram-project" /></template>

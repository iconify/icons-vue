<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsmyl7b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qsmyl7b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:charging-station-15" /></template>

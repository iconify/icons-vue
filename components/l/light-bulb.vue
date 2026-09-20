<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfnw5t5bx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="tfnw5t5bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:light-bulb" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs1c3lqko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":472};
const content = `<path class="vs1c3lqko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:important" /></template>

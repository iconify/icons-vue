<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt8f-3eoh.css';
import '../../css/q/qruqcigga.css';
import '../../css/q/qll7tub0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dt8f-3eoh"/><path class="qruqcigga"/><path class="qll7tub0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-cog-20-bold" /></template>

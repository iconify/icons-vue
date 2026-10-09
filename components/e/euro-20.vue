<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4lq4-bat.css';
import '../../css/q/qv1r8v-de.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g4lq4-bat"/><path class="qv1r8v-de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:euro-20" /></template>

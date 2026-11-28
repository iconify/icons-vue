<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pce7ff9sr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pce7ff9sr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:machine-with-handwheel-and-flat-coin" /></template>

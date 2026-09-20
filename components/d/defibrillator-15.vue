<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni7s91bfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ni7s91bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:defibrillator-15" /></template>

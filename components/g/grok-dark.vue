<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_dwuhmht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f_dwuhmht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:grok-dark" /></template>

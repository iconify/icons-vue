<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/har2xdbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="har2xdbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:full-moon-symbol" /></template>

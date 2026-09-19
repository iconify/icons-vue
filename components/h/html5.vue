<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to-wjbbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="to-wjbbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:html5" /></template>

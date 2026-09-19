<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7x18sbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="o7x18sbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:html" /></template>

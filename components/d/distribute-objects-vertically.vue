<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwj4ck9iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="uwj4ck9iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:distribute-objects-vertically" /></template>

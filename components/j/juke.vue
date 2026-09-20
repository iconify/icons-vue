<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2yv7bc5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2yv7bc5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:juke" /></template>

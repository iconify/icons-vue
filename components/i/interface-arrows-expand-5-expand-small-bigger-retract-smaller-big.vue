<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0kqobc-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="t0kqobc-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-expand-5-expand-small-bigger-retract-smaller-big" /></template>

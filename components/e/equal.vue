<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jeo6qjb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="jeo6qjb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:equal" /></template>

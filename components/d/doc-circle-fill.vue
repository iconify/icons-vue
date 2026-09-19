<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol8f0qb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ol8f0qb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:doc-circle-fill" /></template>

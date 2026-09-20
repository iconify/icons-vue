<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq43k1bqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qq43k1bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:army-tent" /></template>

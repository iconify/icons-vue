<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gba653bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gba653bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:italic" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhsgjb_gi.css';
import '../../css/h/hruqhdmcp.css';
import '../../css/n/n6xeidxlr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vhsgjb_gi"/><path clip-rule="evenodd" class="hruqhdmcp"/><path clip-rule="evenodd" class="n6xeidxlr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:chevron-smooth-left-16" /></template>

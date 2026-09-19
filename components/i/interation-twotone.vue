<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc8-4tb2b.css';
import '../../css/r/rfu4tssqt.css';
import '../../css/d/drwui-btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gc8-4tb2b"/><path class="rfu4tssqt"/><path class="drwui-btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:interation-twotone" /></template>

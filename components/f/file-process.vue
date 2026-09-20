<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv8o2ibxb.css';
import '../../css/q/qkmfhjfvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qv8o2ibxb"/><path class="qkmfhjfvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:file-process" /></template>

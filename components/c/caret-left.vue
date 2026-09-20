<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw9msv4zk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bw9msv4zk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:caret-left" /></template>

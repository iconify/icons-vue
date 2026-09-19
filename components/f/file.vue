<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk2po9bxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zk2po9bxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:file" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhc0zl4zk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qhc0zl4zk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:four" /></template>

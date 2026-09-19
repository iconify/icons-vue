<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2f5krd8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o2f5krd8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:firstaid" /></template>

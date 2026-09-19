<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4xlp0q1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="s4xlp0q1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:ellipsis-horizontal-circle" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8vg3ubnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":648};
const content = `<path class="e8vg3ubnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:graph" /></template>

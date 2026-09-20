<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klsc_6f6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="klsc_6f6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrows-left-right" /></template>

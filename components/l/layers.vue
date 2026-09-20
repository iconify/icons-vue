<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouz__9e9k.css';
import '../../css/c/ctz427bry.css';
import '../../css/v/vkt-pxbju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ouz__9e9k"/><path class="ctz427bry"/><path class="vkt-pxbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:layers" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg1m7vbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jg1m7vbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:diagram-module-library" /></template>

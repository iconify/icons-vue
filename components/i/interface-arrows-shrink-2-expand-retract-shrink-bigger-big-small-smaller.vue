<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_vpwmboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="j_vpwmboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-shrink-2-expand-retract-shrink-bigger-big-small-smaller" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br0wady_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="br0wady_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-expand-3-expand-smaller-retract-bigger-big-small-diagonal" /></template>

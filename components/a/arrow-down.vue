<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx60_7i_g.css';
import '../../css/a/arylohbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx60_7i_g wm-k"/><path class="arylohbyl wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:arrow-down" /></template>

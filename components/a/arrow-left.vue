<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aexwcm9er.css';
import '../../css/c/ccdp7c34j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aexwcm9er wm-k"/><path class="ccdp7c34j wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:arrow-left" /></template>

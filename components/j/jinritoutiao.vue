<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3sx0h80t.css';
import '../../css/j/jz3-sacqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i3sx0h80t"/><path clip-rule="evenodd" class="jz3-sacqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:jinritoutiao" /></template>

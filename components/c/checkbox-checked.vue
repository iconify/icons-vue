<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8tv-ebop.css';
import '../../css/x/xvqdfg4fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8tv-ebop"/><path class="xvqdfg4fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:checkbox-checked" /></template>

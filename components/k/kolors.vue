<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvdf-3beg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yvdf-3beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:kolors" /></template>

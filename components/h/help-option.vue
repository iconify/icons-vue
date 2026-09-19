<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1hxhfb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y1hxhfb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:help-option" /></template>

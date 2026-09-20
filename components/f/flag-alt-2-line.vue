<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc8eo5pxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc8eo5pxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:flag-alt-2-line" /></template>

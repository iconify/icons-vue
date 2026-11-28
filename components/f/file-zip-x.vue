<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfvle8bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfvle8bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-zip-x" /></template>

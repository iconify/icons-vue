<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fid8v8bxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fid8v8bxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:html5" /></template>

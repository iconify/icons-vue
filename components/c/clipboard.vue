<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg4h3hbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jg4h3hbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:clipboard" /></template>

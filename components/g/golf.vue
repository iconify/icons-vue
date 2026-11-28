<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz6z4yblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jz6z4yblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:golf" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay658xbgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ay658xbgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-right-down" /></template>

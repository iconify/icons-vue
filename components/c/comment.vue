<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jscfo15-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jscfo15-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:comment" /></template>

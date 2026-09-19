<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc277abge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc277abge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:cbs" /></template>

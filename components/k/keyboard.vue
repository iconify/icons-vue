<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb23s1bng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb23s1bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:keyboard" /></template>

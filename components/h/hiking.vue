<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yja1tab9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yja1tab9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hiking" /></template>

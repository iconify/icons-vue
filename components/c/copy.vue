<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbg7job8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pbg7job8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:copy" /></template>

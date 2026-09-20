<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs2kr799c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vs2kr799c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:link-square-filled" /></template>

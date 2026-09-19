<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaxyklglx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yaxyklglx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:link-alt-01" /></template>

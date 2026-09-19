<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs2dvebnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bs2dvebnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:align-text-justify-right" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2w0dmuau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t2w0dmuau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:cube-alt-02-filled" /></template>

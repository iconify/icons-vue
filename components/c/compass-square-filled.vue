<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2d24brxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s2d24brxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:compass-square-filled" /></template>

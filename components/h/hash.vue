<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx4l9z1qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xx4l9z1qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:hash" /></template>

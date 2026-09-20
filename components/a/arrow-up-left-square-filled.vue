<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixisz2b4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ixisz2b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-up-left-square-filled" /></template>

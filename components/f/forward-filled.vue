<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjusi5q4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pjusi5q4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:forward-filled" /></template>

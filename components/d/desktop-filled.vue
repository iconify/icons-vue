<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdb3-q2ts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hdb3-q2ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:desktop-filled" /></template>

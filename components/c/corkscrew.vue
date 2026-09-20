<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw47y_bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yw47y_bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:corkscrew" /></template>

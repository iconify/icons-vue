<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yewil7zys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yewil7zys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hierarchy-square-filled" /></template>

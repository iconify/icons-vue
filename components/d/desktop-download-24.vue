<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yovgyab1e.css';
import '../../css/x/x218cyb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yovgyab1e"/><path class="x218cyb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:desktop-download-24" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqy9tkbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqy9tkbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-output" /></template>

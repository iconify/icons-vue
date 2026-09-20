<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se1bk8kjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se1bk8kjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bohemia-interactive" /></template>

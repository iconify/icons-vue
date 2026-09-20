<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb5ewbbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jb5ewbbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lan-disconnect" /></template>

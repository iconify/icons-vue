<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkcm51b9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkcm51b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:lightbulb-circle-filled" /></template>

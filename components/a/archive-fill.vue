<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvg5uvnqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvg5uvnqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:archive-fill" /></template>

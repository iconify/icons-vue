<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olwaxit4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olwaxit4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:caret-up-small" /></template>

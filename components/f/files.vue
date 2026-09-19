<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbt9mqbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbt9mqbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:files" /></template>

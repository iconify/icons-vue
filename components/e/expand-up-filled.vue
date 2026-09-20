<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjrm-7bqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjrm-7bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:expand-up-filled" /></template>

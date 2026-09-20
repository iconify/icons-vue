<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x969onb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x969onb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:building-5-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik4pm6qxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik4pm6qxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:corn-filled" /></template>

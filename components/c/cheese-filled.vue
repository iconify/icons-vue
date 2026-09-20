<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-ad92bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-ad92bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:cheese-filled" /></template>

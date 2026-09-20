<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgejtq3gs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgejtq3gs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:magisk" /></template>

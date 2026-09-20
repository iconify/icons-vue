<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi5e1i3tl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi5e1i3tl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:devbox" /></template>

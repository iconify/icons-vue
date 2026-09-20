<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f28nl8btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f28nl8btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:iflytekcloud" /></template>

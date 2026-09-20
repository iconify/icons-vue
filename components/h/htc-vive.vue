<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1uailbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1uailbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:htc-vive" /></template>

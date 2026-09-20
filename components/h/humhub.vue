<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc2x0wbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc2x0wbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:humhub" /></template>

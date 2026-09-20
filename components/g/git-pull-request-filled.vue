<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v06x-3-pj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v06x-3-pj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:git-pull-request-filled" /></template>

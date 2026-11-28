<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue7jy582w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue7jy582w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:git-pull-request-solid" /></template>

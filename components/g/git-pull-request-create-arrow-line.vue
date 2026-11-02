<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prlh_wbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prlh_wbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-pull-request-create-arrow-line" /></template>

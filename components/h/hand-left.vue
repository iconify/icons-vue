<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy54xbb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy54xbb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:hand-left" /></template>

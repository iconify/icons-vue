<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo_xvzb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo_xvzb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevron-right-duo" /></template>

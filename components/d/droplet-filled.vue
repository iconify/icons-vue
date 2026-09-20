<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zba_mr_xo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zba_mr_xo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:droplet-filled" /></template>

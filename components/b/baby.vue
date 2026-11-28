<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwn-dpbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwn-dpbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:baby" /></template>

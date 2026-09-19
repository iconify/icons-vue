<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh5ca-63n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh5ca-63n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-big-up-line-filled" /></template>

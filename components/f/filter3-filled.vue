<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rok7fibkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rok7fibkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:filter3-filled" /></template>

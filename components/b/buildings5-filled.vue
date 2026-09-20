<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xanmli5fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xanmli5fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:buildings5-filled" /></template>

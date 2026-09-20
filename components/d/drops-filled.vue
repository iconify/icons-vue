<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twhk86b2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twhk86b2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:drops-filled" /></template>

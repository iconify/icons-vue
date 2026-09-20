<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdxsa5ggx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hdxsa5ggx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:confused-circle-filled" /></template>

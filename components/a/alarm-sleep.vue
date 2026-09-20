<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl9ze4myq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tl9ze4myq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:alarm-sleep" /></template>

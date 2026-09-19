<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8dcjwbei.css';
import '../../css/d/di5phmx8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b x8dcjwbei"/><path class="b di5phmx8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:camera-alt-filled" /></template>

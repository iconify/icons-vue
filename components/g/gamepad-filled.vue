<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvjr2x3go.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mvjr2x3go"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gamepad-filled" /></template>

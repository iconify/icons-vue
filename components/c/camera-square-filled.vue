<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at5nmb45p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="at5nmb45p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:camera-square-filled" /></template>

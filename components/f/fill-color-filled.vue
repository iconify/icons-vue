<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m42sphumz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m42sphumz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:fill-color-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at5p92bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="at5p92bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:location-error-filled" /></template>

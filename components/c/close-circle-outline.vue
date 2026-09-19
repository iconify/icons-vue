<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wckr9kb1z.css';
import '../../css/d/d7vyowb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wckr9kb1z"/><path class="d7vyowb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:close-circle-outline" /></template>

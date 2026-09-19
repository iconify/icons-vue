<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiet4yv0k.css';
import '../../css/t/tiru1tbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yiet4yv0k"/><path class="tiru1tbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-user-voice" /></template>

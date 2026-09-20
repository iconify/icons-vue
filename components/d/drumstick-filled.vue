<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lueh_ubrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lueh_ubrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:drumstick-filled" /></template>

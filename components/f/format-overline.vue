<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/objpm4zrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="objpm4zrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-overline" /></template>

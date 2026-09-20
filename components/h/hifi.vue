<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4_e1os6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4_e1os6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hifi" /></template>

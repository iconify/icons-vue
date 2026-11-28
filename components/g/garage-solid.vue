<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmimakb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nmimakb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:garage-solid" /></template>

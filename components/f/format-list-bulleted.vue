<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk11j18xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk11j18xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-list-bulleted" /></template>

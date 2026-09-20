<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd35avbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd35avbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:key-change" /></template>

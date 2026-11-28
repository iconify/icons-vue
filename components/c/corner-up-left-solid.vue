<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s28b8lbtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s28b8lbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:corner-up-left-solid" /></template>

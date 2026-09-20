<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c27nap3uv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c27nap3uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:box-edit" /></template>

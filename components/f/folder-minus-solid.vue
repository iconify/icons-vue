<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gar376luf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gar376luf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:folder-minus-solid" /></template>

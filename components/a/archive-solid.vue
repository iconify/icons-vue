<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt4i8hbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt4i8hbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:archive-solid" /></template>

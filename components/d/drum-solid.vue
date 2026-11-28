<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av5mm9bdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="av5mm9bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:drum-solid" /></template>

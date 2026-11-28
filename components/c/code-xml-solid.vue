<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tob1ebbhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tob1ebbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:code-xml-solid" /></template>

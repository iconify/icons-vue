<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rccc1p87j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rccc1p87j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fruit-cherries" /></template>

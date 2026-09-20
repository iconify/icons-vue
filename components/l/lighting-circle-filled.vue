<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctkzpqbcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctkzpqbcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:lighting-circle-filled" /></template>

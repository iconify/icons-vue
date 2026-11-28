<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsl08fp4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsl08fp4r primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:curtains-open-duotone" /></template>

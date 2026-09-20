<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2l_fub7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2l_fub7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bookmark" /></template>

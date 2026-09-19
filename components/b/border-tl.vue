<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqq4bzftk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqq4bzftk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:border-tl" /></template>

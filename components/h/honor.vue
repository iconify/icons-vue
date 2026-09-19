<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dou5g5byt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dou5g5byt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:honor" /></template>

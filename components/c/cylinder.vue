<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piu1gj3kk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="piu1gj3kk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:cylinder" /></template>

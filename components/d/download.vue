<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtw3e_bsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtw3e_bsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:download" /></template>

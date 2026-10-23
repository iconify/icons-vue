<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsptjqbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsptjqbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mail-pen" /></template>

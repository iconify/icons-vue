<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6yrju2ef.css';
import '../../css/o/opsksqbxj.css';
import '../../css/v/vn4va-blz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6yrju2ef"/><circle class="opsksqbxj"/><circle class="vn4va-blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-message-square-dots" /></template>

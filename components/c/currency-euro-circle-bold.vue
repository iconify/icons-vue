<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw-0sgbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw-0sgbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:currency-euro-circle-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-61lmm4b.css';
import '../../css/v/v-wrjcb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-61lmm4b"/><path class="v-wrjcb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:font-size-bold" /></template>

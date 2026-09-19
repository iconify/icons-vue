<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slsyuwjqx.css';
import '../../css/y/yd2zepbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slsyuwjqx"/><path clip-rule="evenodd" class="yd2zepbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:css-fill" /></template>

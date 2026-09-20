<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfdiclobe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfdiclobe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:function-variant" /></template>

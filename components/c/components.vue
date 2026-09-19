<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz8zeq7tn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wz8zeq7tn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:components" /></template>

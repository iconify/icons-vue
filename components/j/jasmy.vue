<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf19libts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pf19libts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:jasmy" /></template>

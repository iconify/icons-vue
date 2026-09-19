<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrd764yhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wrd764yhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:equal-fill" /></template>

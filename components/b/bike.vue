<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewhk_6ffn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewhk_6ffn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bike" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmp48z4el.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmp48z4el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:color" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct5_d9bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ct5_d9bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:clipboard" /></template>

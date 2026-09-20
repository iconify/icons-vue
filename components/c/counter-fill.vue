<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx-ivcb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bx-ivcb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:counter-fill" /></template>

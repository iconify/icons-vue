<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0p6avbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0p6avbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-indent-increase-line" /></template>

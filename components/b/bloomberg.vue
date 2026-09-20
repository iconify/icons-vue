<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1xlz4bth.css';
import '../../css/o/ordys2bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1xlz4bth"/><path class="ordys2bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bloomberg" /></template>

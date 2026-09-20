<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye9ypdw-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye9ypdw-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:backward-filled" /></template>

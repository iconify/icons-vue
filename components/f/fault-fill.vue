<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abrao85rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="abrao85rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fault-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/taacmzukk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="taacmzukk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-x-fill" /></template>

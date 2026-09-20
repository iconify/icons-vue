<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3ceodbcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z3ceodbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:laptop-fill" /></template>

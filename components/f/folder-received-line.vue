<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3p00mgpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3p00mgpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-received-line" /></template>

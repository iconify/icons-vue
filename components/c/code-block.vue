<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teb7xlbof.css';
import '../../css/m/mnjmwzb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="teb7xlbof"/><path class="mnjmwzb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:code-block" /></template>

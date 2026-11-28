<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3pk0v5as.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3pk0v5as"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bow-tie" /></template>

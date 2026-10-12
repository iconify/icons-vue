<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf2yuuixj.css';
import '../../css/r/rwu1_obmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cf2yuuixj"/><path class="rwu1_obmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bone-fracture-filled" /></template>

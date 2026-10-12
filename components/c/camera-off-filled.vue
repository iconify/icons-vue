<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceheq--eq.css';
import '../../css/o/oed997bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ceheq--eq"/><path class="oed997bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:camera-off-filled" /></template>

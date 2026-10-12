<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtsjshfvz.css';
import '../../css/m/m1cu4sbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mtsjshfvz"/><path class="m1cu4sbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mail-badge-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ickn83b4x.css';
import '../../css/x/xn5murb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ickn83b4x"/><path clip-rule="evenodd" class="xn5murb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-letter-a-filled" /></template>

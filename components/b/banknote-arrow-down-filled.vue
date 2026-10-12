<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksderlvfw.css';
import '../../css/a/a08-prbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksderlvfw"/><path clip-rule="evenodd" class="a08-prbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:banknote-arrow-down-filled" /></template>

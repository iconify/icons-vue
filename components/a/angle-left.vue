<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lzl0cwb5v.css';
import '../../css/k/knq4cqwzw.css';
import '../../css/u/ufhld3mmu.css';
import '../../css/v/vbuonu-3b.css';
import '../../css/i/ivigl7ula.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="lzl0cwb5v"/><path class="knq4cqwzw"/><path class="ufhld3mmu"/><path class="vbuonu-3b"/><path class="ivigl7ula"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:angle-left" /></template>

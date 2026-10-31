<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fra7p-djj.css';
import '../../css/t/t_2-m239s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="fra7p-djj"/><path class="t_2-m239s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:european-union" /></template>

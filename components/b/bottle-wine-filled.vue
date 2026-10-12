<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn3ycljxj.css';
import '../../css/l/lfs1rybvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xn3ycljxj"/><path class="lfs1rybvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bottle-wine-filled" /></template>

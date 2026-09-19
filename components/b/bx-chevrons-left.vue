<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_2io5_mv.css';
import '../../css/c/ckipxtbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_2io5_mv"/><path class="ckipxtbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-chevrons-left" /></template>

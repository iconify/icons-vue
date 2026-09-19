<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgo18hbkg.css';
import '../../css/h/hd_yihbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgo18hbkg"/><path class="hd_yihbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:down-arrow-circle" /></template>

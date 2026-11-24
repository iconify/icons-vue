<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg84ptbsf.css';
import '../../css/t/tl712yvzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gg84ptbsf"/><path class="tl712yvzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:alarm-clock-filled" /></template>

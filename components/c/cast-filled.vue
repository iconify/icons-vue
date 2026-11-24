<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sthnq_bas.css';
import '../../css/r/rm7c5vbvg.css';
import '../../css/d/dawzjdknl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sthnq_bas"/><path class="rm7c5vbvg"/><path class="dawzjdknl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cast-filled" /></template>

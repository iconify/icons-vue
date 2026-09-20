<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ges_wsysv.css';
import '../../css/f/fcjlr1v_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ges_wsysv"/><path clip-rule="evenodd" class="fcjlr1v_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-archive-fill" /></template>

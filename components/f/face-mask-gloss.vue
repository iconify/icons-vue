<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pev7asabd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pev7asabd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:face-mask-gloss" /></template>

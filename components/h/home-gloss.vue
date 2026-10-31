<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb1_zvdgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb1_zvdgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:home-gloss" /></template>

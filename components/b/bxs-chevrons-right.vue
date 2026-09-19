<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp7_n3beu.css';
import '../../css/b/bxv5csb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp7_n3beu"/><path class="bxv5csb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-chevrons-right" /></template>

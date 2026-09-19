<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq04ipdji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rq04ipdji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:data-transfer-up" /></template>

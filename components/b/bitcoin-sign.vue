<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdtyl-iiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdtyl-iiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:bitcoin-sign" /></template>

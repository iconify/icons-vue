<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr8mm2bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr8mm2bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:float-left" /></template>

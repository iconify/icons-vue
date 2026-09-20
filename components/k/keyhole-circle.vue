<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqbu23bhp.css';
import '../../css/n/nlx9a6xnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqbu23bhp"/><path class="nlx9a6xnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:keyhole-circle" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqbu23bhp.css';
import '../../css/n/ndzxj5bdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqbu23bhp"/><path class="ndzxj5bdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:keyhole-square" /></template>

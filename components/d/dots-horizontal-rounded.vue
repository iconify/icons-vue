<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h96ml7bnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h96ml7bnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:dots-horizontal-rounded" /></template>

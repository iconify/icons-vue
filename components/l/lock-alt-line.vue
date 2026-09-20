<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3j-qp_1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3j-qp_1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:lock-alt-line" /></template>

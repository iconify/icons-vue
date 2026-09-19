<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qopmer22v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qopmer22v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-chevron-right-circle" /></template>

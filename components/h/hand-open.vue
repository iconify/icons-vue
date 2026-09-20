<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp3_0nbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp3_0nbpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-open" /></template>

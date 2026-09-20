<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc3rm6i6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qc3rm6i6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:layout-minus" /></template>

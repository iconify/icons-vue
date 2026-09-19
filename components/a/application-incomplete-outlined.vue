<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t683n5mpp.css';
import '../../css/t/tssojcb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t683n5mpp"/><path class="tssojcb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:application-incomplete-outlined" /></template>

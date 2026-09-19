<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcfniyu4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcfniyu4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:list-checklist-alt" /></template>

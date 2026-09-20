<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1aks1oms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q1aks1oms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:division-math-symbol-circle-bold" /></template>

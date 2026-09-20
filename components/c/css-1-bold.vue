<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq-dyqsyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eq-dyqsyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:css-1-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qagp4hexa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qagp4hexa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:arrow-circle-down-left" /></template>

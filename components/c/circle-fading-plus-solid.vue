<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf-pqzgog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qf-pqzgog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-fading-plus-solid" /></template>

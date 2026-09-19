<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcvn449qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcvn449qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:align-justify" /></template>

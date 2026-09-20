<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4p_l0bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o4p_l0bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:compass2" /></template>

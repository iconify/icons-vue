<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1u1o_u1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-3};
const content = `<path class="w1u1o_u1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:brush" /></template>

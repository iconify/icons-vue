<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0i8e_bes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0i8e_bes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-message" /></template>

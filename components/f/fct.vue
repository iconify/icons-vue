<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwf_gumjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwf_gumjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fct" /></template>

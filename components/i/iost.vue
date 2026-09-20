<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hy_fhzbzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hy_fhzbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:iost" /></template>

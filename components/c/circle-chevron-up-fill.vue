<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw6_glbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yw6_glbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:circle-chevron-up-fill" /></template>
